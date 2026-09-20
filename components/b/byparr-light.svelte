<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe529yltx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xe529yltx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:byparr-light" {...props}></Icon>
