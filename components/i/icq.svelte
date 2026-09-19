<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e79s1fb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":981.393,"height":1000};
const content = `<path class="e79s1fb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:icq" {...props}></Icon>
