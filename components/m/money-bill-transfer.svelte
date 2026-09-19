<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn1nicbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jn1nicbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:money-bill-transfer" {...props}></Icon>
