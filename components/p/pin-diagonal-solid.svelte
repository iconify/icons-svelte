<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqm2czb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqm2czb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pin-diagonal-solid" {...props}></Icon>
