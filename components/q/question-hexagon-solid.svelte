<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa1unaboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xa1unaboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:question-hexagon-solid" {...props}></Icon>
