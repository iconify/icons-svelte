<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikj9gwsrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ikj9gwsrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:megaphone-fill-20" {...props}></Icon>
