<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf7ni6b2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jf7ni6b2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:airport-plane-remix" {...props}></Icon>
