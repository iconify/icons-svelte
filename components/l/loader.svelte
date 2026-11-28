<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm9y-eble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cm9y-eble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:loader" {...props}></Icon>
