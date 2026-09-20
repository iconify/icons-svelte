<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czrzz41ep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czrzz41ep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:alarm3-filled" {...props}></Icon>
