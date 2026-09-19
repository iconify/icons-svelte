<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly7-gdbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ly7-gdbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:eleme" {...props}></Icon>
