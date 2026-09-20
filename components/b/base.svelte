<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h65wv1-tj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h65wv1-tj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:base" {...props}></Icon>
