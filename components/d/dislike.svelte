<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/heoriabzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="heoriabzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:dislike" {...props}></Icon>
