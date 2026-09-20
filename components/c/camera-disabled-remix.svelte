<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/toe58qfqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="toe58qfqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:camera-disabled-remix" {...props}></Icon>
