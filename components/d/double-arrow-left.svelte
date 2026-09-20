<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkljacc9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkljacc9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:double-arrow-left" {...props}></Icon>
