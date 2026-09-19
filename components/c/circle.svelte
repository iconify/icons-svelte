<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwqu0vbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<circle class="iwqu0vbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:circle" {...props}></Icon>
