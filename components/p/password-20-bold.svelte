<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf-xb_4oc.css';
import '../../css/h/h-eujcczx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qf-xb_4oc"/><path class="h-eujcczx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:password-20-bold" {...props}></Icon>
