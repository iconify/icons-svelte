<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3vh0625f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3vh0625f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-circle-question-solid" {...props}></Icon>
