<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlparkbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlparkbxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rar-01" {...props}></Icon>
