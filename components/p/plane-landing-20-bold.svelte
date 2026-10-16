<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/davndjhkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="davndjhkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plane-landing-20-bold" {...props}></Icon>
