<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh7682bbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xh7682bbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:burger-arrow-left" {...props}></Icon>
