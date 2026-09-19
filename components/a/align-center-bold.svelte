<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_l676bku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="v_l676bku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:align-center-bold" {...props}></Icon>
