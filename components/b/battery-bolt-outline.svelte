<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikh-14usx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ikh-14usx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-bolt-outline" {...props}></Icon>
