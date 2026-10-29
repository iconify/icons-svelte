<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kffe7kb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kffe7kb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:hospital-solid" {...props}></Icon>
