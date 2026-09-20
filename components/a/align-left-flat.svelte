<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js0cebkwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="js0cebkwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:align-left-flat" {...props}></Icon>
