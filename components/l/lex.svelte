<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkxxtlbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":500,"height":512};
const content = `<path clip-rule="evenodd" class="qkxxtlbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:lex" {...props}></Icon>
