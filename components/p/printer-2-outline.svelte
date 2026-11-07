<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myod-k65i.css';
import '../../css/i/ihkre-bnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="myod-k65i"/><path class="ihkre-bnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:printer-2-outline" {...props}></Icon>
