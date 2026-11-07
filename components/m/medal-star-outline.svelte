<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzs94db-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xzs94db-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-star-outline" {...props}></Icon>
