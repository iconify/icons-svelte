<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh1omzxpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="fh1omzxpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:app-menu" {...props}></Icon>
