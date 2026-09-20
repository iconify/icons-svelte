<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir0t33bvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ir0t33bvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:rocket-2-sharp" {...props}></Icon>
