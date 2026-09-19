<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8lv_jb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":751,"height":785};
const content = `<path class="z8lv_jb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:at" {...props}></Icon>
