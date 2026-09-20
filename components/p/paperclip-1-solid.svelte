<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orjk9nbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="orjk9nbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:paperclip-1-solid" {...props}></Icon>
