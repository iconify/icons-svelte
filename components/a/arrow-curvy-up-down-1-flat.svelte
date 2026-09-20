<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0gee4-iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g0gee4-iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-curvy-up-down-1-flat" {...props}></Icon>
