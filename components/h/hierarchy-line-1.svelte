<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epwuo5bgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epwuo5bgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:hierarchy-line-1" {...props}></Icon>
