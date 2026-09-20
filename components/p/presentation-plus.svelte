<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elkic2khp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elkic2khp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:presentation-plus" {...props}></Icon>
