<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9lb6ysvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9lb6ysvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:notes" {...props}></Icon>
