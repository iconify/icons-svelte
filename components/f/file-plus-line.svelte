<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgeel1b_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgeel1b_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:file-plus-line" {...props}></Icon>
