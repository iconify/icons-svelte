<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkd8ybcyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkd8ybcyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:messanger" {...props}></Icon>
