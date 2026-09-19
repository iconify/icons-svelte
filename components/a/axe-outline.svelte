<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9w2xqbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="o9w2xqbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:axe-outline" {...props}></Icon>
