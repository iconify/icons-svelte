<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vubs4oo9h.css';
import '../../css/c/cohq8848r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vubs4oo9h"/><path class="cohq8848r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-sun-48-bold" {...props}></Icon>
