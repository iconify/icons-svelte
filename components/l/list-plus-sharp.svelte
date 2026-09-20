<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prwr0bcqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prwr0bcqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-plus-sharp" {...props}></Icon>
