<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbt47ybki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="tbt47ybki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:bin-xmark-fill" {...props}></Icon>
