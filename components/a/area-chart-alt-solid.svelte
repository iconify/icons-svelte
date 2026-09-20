<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm-i-ub8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cm-i-ub8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:area-chart-alt-solid" {...props}></Icon>
