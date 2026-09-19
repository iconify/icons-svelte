<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egwn_np2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="egwn_np2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:comment-asterisk-bold" {...props}></Icon>
