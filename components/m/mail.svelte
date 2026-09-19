<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr_oojzww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zr_oojzww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:mail" {...props}></Icon>
