<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya2h1ewyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ya2h1ewyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:flash-2-flat" {...props}></Icon>
