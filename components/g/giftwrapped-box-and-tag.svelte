<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdu7zo3md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tdu7zo3md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:giftwrapped-box-and-tag" {...props}></Icon>
