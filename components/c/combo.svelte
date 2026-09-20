<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akiw1abux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akiw1abux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:combo" {...props}></Icon>
