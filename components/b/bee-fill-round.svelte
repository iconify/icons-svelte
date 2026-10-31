<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d31hp5hth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d31hp5hth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bee-fill-round" {...props}></Icon>
