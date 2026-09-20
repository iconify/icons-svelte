<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er3j_9bxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er3j_9bxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:drooble" {...props}></Icon>
