<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2x0wbcne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2x0wbcne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mining-02" {...props}></Icon>
