<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pft_zib7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="pft_zib7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:doc" {...props}></Icon>
