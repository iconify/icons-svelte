<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxo764bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxo764bau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:aas-shell-export" {...props}></Icon>
