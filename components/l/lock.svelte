<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6vai-59c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c6vai-59c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:lock" {...props}></Icon>
