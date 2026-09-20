<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbx5hlb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vbx5hlb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:buildings-3-outline" {...props}></Icon>
