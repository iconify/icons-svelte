<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1cd96b6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x1cd96b6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:equal-sign-flat" {...props}></Icon>
