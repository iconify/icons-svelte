<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-z9upbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="a-z9upbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:lips" {...props}></Icon>
