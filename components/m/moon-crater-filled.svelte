<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtsoh-dhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtsoh-dhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:moon-crater-filled" {...props}></Icon>
