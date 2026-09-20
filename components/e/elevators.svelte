<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf-x9x4-a.css';
import '../../css/j/j2fntcc6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":63,"height":64};
const content = `<path class="mf-x9x4-a"/><path class="j2fntcc6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:elevators" {...props}></Icon>
