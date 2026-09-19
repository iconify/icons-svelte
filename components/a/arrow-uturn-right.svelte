<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5n4_s5eb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="b5n4_s5eb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-uturn-right" {...props}></Icon>
