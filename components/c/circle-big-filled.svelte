<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctuz6eght.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ctuz6eght"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:circle-big-filled" {...props}></Icon>
