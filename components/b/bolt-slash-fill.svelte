<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8m7-jz1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="u8m7-jz1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:bolt-slash-fill" {...props}></Icon>
