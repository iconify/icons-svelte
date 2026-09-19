<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj7b05b-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mj7b05b-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:globe" {...props}></Icon>
