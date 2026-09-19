<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgyb2p1_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jgyb2p1_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:evernote" {...props}></Icon>
