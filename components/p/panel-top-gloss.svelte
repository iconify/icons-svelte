<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7ka5bc5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7ka5bc5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:panel-top-gloss" {...props}></Icon>
