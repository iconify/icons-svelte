<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwuut5b3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mwuut5b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-right-20" {...props}></Icon>
