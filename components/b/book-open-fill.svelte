<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7bbzukac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7bbzukac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:book-open-fill" {...props}></Icon>
