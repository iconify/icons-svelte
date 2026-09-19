<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivqa_53qu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivqa_53qu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:add-selection" {...props}></Icon>
