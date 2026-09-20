<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaedl0tuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qaedl0tuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:puppet" {...props}></Icon>
