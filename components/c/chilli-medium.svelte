<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkjjnzrxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hkjjnzrxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chilli-medium" {...props}></Icon>
