<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lktgmqyfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":120};
const content = `<path class="lktgmqyfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bajaj-auto" {...props}></Icon>
