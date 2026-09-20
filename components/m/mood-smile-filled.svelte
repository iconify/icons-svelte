<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc0lycc_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc0lycc_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mood-smile-filled" {...props}></Icon>
