<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdq8m0blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdq8m0blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:mullvad" {...props}></Icon>
