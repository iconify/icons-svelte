<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfexlwteu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jfexlwteu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:chat-alt" {...props}></Icon>
