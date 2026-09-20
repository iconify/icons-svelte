<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmg5pabex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmg5pabex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:pinboard" {...props}></Icon>
