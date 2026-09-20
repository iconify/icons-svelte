<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td8wbxbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="td8wbxbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:music-equalizer-solid" {...props}></Icon>
