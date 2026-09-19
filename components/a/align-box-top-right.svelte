<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5jfrdb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5jfrdb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-box-top-right" {...props}></Icon>
