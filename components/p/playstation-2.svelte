<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai732kenn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ai732kenn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:playstation-2" {...props}></Icon>
