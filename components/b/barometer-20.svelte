<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw3xaacjo.css';
import '../../css/t/td2ls7bcf.css';
import '../../css/e/e8w13wbpk.css';
import '../../css/m/m9xus8rcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yw3xaacjo"/><path class="td2ls7bcf"/><path class="e8w13wbpk"/><path class="m9xus8rcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:barometer-20" {...props}></Icon>
