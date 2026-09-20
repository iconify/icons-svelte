<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcdy8nbzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="lcdy8nbzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:paint-roller-1" {...props}></Icon>
