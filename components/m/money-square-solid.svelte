<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dswrzxb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dswrzxb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:money-square-solid" {...props}></Icon>
