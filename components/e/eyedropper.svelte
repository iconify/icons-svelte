<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5j_ri7jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="k5j_ri7jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:eyedropper" {...props}></Icon>
