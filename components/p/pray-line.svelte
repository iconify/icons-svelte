<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnw8g3zvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnw8g3zvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pray-line" {...props}></Icon>
