<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs8p12bia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="bs8p12bia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:alien" {...props}></Icon>
