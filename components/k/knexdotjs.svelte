<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d04ehj19u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d04ehj19u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:knexdotjs" {...props}></Icon>
