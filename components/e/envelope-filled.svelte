<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpqqn6bis.css';
import '../../css/r/rln8920_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpqqn6bis"/><path class="rln8920_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:envelope-filled" {...props}></Icon>
