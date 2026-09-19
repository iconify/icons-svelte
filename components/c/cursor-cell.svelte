<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otiut1bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otiut1bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cursor-cell" {...props}></Icon>
