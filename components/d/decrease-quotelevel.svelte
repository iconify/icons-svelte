<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx80h9bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="rx80h9bhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:decrease-quotelevel" {...props}></Icon>
