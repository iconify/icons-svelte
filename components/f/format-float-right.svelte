<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmxskzbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmxskzbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:format-float-right" {...props}></Icon>
