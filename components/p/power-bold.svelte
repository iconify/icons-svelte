<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvhv_7sne.css';
import '../../css/x/xrl_dh1so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvhv_7sne"/><path class="xrl_dh1so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:power-bold" {...props}></Icon>
