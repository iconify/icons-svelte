<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feumftmof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="feumftmof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bookmark-plus-solid" {...props}></Icon>
