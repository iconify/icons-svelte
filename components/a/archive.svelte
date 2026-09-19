<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xec99qfcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xec99qfcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:archive" {...props}></Icon>
