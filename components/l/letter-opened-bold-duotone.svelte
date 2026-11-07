<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-k_gnknn.css';
import '../../css/h/hvs5gsb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x-k_gnknn"/><path class="hvs5gsb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:letter-opened-bold-duotone" {...props}></Icon>
