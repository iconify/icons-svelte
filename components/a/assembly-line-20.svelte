<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_n5ny1ok.css';
import '../../css/m/m35anv3rp.css';
import '../../css/j/jayc3895l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d_n5ny1ok"/><path class="m35anv3rp"/><path class="jayc3895l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:assembly-line-20" {...props}></Icon>
