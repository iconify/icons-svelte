<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt0urabjs.css';
import '../../css/m/mgxmn9o8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rt0urabjs"/><path class="mgxmn9o8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:filter-duotone" {...props}></Icon>
