<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8eaadcrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8eaadcrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mouse-pointer-filled" {...props}></Icon>
