<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb658b_kg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bb658b_kg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-y-square-solid" {...props}></Icon>
