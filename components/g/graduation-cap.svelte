<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwwn-tela.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1536};
const content = `<path class="nwwn-tela"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:graduation-cap" {...props}></Icon>
