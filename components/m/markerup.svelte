<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksw-7fbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="ksw-7fbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:markerup" {...props}></Icon>
