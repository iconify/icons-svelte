<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tin16p2kl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="tin16p2kl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:compass-fill" {...props}></Icon>
