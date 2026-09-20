<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa4gzdbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qa4gzdbgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-big-right-short-sharp-duotone" {...props}></Icon>
