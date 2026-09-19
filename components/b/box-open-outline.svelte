<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpx0u7qjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="wpx0u7qjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:box-open-outline" {...props}></Icon>
