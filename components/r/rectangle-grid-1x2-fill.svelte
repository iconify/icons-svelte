<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9gf-lmhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="w9gf-lmhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-grid-1x2-fill" {...props}></Icon>
