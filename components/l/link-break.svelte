<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyj42ylez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyj42ylez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:link-break" {...props}></Icon>
