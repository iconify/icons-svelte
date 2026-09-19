<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyo01_bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1792};
const content = `<path class="hyo01_bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:mars-double" {...props}></Icon>
