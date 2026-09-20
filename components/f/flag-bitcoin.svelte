<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwlc1fzvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwlc1fzvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:flag-bitcoin" {...props}></Icon>
