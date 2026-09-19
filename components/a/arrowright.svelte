<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bky_spooe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1025};
const content = `<path class="bky_spooe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:arrowright" {...props}></Icon>
