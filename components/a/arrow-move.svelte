<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inwxpsb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="inwxpsb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:arrow-move" {...props}></Icon>
