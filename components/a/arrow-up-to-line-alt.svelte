<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfex-sbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="hfex-sbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-up-to-line-alt" {...props}></Icon>
