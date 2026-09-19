<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v88f60b3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="v88f60b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:hashtag-line" {...props}></Icon>
