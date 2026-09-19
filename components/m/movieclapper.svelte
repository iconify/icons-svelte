<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bthpj2-gq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":1024};
const content = `<path class="bthpj2-gq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:movieclapper" {...props}></Icon>
