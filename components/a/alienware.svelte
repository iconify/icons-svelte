<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/daw-5ibwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="daw-5ibwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:alienware" {...props}></Icon>
