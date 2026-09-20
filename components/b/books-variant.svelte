<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcc-r0bkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tcc-r0bkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:books-variant" {...props}></Icon>
