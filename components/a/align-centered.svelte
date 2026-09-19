<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1yw06b1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":448};
const content = `<path class="h1yw06b1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:align-centered" {...props}></Icon>
