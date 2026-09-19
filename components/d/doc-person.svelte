<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7ns0-bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="d7ns0-bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:doc-person" {...props}></Icon>
