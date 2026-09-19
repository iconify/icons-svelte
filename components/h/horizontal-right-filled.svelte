<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czzrfsbop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czzrfsbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:horizontal-right-filled" {...props}></Icon>
