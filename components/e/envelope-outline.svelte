<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqeq75bqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="jqeq75bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:envelope-outline" {...props}></Icon>
