<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg8nthb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dg8nthb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:insurance-hand-1-remix" {...props}></Icon>
