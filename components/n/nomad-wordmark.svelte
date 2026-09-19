<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl5zwabiv.css';
import '../../css/q/qm-avg1-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="yl5zwabiv"/><path class="qm-avg1-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nomad-wordmark" {...props}></Icon>
