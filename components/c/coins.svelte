<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4w54bcpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4w54bcpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:coins" {...props}></Icon>
