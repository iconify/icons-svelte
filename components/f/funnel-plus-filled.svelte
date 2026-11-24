<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3e-_2bze.css';
import '../../css/n/n6-kt6b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3e-_2bze"/><path class="n6-kt6b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:funnel-plus-filled" {...props}></Icon>
