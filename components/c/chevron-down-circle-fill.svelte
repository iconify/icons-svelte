<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-f4ob-1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-f4ob-1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:chevron-down-circle-fill" {...props}></Icon>
