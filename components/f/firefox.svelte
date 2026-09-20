<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiz3a5bdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fiz3a5bdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:firefox" {...props}></Icon>
