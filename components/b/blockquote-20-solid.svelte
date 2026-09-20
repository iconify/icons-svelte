<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkwi5f_-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nkwi5f_-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:blockquote-20-solid" {...props}></Icon>
