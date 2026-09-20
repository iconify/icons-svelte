<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku24kpydw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="ku24kpydw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:heart" {...props}></Icon>
