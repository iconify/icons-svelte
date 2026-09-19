<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm-n87bpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nm-n87bpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:book-open-reader" {...props}></Icon>
