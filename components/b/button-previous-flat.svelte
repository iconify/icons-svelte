<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg-t2lq9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sg-t2lq9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:button-previous-flat" {...props}></Icon>
