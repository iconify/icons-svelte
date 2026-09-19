<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej_ysgt9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ej_ysgt9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:arrow-up-right-square" {...props}></Icon>
