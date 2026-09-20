<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlga79byl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlga79byl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ghost-smile-fill" {...props}></Icon>
