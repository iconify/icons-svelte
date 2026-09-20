<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-7oyebwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-7oyebwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:flickr-logo" {...props}></Icon>
