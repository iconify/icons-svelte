<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/paer3lxos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="paer3lxos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-peace-bold" {...props}></Icon>
