<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkdiqpb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wkdiqpb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:asterisk-1-remix" {...props}></Icon>
