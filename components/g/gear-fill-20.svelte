<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8swt4bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g8swt4bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:gear-fill-20" {...props}></Icon>
