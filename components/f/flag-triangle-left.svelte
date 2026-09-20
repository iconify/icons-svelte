<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psqu8mbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psqu8mbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:flag-triangle-left" {...props}></Icon>
