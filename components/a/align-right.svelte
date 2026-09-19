<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/girn4kpqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":448};
const content = `<path class="girn4kpqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:align-right" {...props}></Icon>
