<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo0137bkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oo0137bkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:fish-alt-filled" {...props}></Icon>
