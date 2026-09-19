<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvj0zbknd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvj0zbknd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:arrival" {...props}></Icon>
