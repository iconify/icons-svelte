<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-r8ydbim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="m-r8ydbim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:envelope-open-outline" {...props}></Icon>
