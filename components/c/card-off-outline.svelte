<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdttxe_0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdttxe_0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:card-off-outline" {...props}></Icon>
