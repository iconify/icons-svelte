<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/darp4o0pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="darp4o0pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-alt-2-duotone" {...props}></Icon>
