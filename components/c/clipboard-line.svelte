<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md7dt_b0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md7dt_b0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:clipboard-line" {...props}></Icon>
