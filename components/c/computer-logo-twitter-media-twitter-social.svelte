<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bic91mcwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="bic91mcwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:computer-logo-twitter-media-twitter-social" {...props}></Icon>
