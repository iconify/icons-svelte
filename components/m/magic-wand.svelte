<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwa1tvb5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwa1tvb5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:magic-wand" {...props}></Icon>
