<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy9r95yun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="cy9r95yun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:retweet" {...props}></Icon>
