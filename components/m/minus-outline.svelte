<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmev9mbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="qmev9mbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:minus-outline" {...props}></Icon>
