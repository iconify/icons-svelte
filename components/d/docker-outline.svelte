<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu08c4b4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hu08c4b4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:docker-outline" {...props}></Icon>
