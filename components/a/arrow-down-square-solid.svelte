<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue3bd1bkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue3bd1bkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-down-square-solid" {...props}></Icon>
