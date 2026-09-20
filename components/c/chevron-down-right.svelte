<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hewnh0kei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hewnh0kei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-down-right" {...props}></Icon>
