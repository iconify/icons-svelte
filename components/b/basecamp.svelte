<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyyw8y90x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="wyyw8y90x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:basecamp" {...props}></Icon>
