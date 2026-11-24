<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwt8ei2ip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rwt8ei2ip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:plug-slash-16-solid" {...props}></Icon>
