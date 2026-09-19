<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjjd_7sue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1280};
const content = `<path class="pjjd_7sue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:inbox" {...props}></Icon>
