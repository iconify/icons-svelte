<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh5-xi8gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kh5-xi8gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:despise-filled" {...props}></Icon>
