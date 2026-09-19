<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mms97ybfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":696};
const content = `<path class="mms97ybfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:busalt" {...props}></Icon>
