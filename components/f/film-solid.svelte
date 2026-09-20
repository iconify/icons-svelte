<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvq-20bfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vvq-20bfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:film-solid" {...props}></Icon>
