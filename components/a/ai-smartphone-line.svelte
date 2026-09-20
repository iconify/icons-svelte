<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2gb0y6gz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2gb0y6gz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-smartphone-line" {...props}></Icon>
