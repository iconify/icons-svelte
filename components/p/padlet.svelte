<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzx64zf2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jzx64zf2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:padlet" {...props}></Icon>
