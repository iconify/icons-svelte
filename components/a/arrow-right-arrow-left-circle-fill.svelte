<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm-to-bdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="nm-to-bdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-right-arrow-left-circle-fill" {...props}></Icon>
