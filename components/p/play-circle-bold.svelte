<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpj_vsb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="wpj_vsb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:play-circle-bold" {...props}></Icon>
