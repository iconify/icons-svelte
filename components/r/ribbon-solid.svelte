<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoxxp1nog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eoxxp1nog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ribbon-solid" {...props}></Icon>
