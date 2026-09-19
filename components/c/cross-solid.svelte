<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijnoz5bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijnoz5bge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:cross-solid" {...props}></Icon>
