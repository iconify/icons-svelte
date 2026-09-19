<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiq6z9xnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kiq6z9xnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:basketball-sharp" {...props}></Icon>
