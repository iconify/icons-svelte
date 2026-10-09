<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htkol23wy.css';
import '../../css/c/c682obb9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="htkol23wy"/><path class="c682obb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:building-48" {...props}></Icon>
