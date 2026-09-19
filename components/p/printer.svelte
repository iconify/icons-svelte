<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfzrj0rbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nfzrj0rbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:printer" {...props}></Icon>
