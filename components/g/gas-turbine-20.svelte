<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlenow6rc.css';
import '../../css/l/l6xz3eb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wlenow6rc"/><path class="l6xz3eb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-turbine-20" {...props}></Icon>
