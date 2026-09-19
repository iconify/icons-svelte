<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po68ny4my.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="po68ny4my"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:on-holiday-solid" {...props}></Icon>
