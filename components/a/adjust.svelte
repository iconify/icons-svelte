<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl87nh5pk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cl87nh5pk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:adjust" {...props}></Icon>
