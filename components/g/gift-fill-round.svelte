<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9eqlg5aq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9eqlg5aq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:gift-fill-round" {...props}></Icon>
