<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-ud2gb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r-ud2gb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:double-up" {...props}></Icon>
