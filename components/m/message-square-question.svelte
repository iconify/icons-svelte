<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvkj3wbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvkj3wbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:message-square-question" {...props}></Icon>
