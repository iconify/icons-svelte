<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln16226oo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ln16226oo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:phone-notification" {...props}></Icon>
