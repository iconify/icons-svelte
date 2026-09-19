<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shgrc6-hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="shgrc6-hf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-2-fill" {...props}></Icon>
