<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms3homc2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ms3homc2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:desk" {...props}></Icon>
