<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inixre9_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="inixre9_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:envelope-badge-fill" {...props}></Icon>
