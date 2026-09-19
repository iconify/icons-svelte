<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg33djbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hg33djbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-fist-outline" {...props}></Icon>
