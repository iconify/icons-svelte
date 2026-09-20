<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k37us7biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k37us7biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:apple-news" {...props}></Icon>
