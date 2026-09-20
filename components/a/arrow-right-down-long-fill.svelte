<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m112204ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m112204ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-right-down-long-fill" {...props}></Icon>
