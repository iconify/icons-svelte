<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epewaqblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="epewaqblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:eye-closed" {...props}></Icon>
