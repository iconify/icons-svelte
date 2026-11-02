<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dal0b0eku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dal0b0eku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-fading-plus-fill" {...props}></Icon>
