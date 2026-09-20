<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e151-8wyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e151-8wyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:desktop-favorite-star-solid" {...props}></Icon>
