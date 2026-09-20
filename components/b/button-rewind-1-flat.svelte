<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5yxx3pqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q5yxx3pqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:button-rewind-1-flat" {...props}></Icon>
