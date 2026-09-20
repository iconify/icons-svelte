<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9wrg4psw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p9wrg4psw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:mail" {...props}></Icon>
