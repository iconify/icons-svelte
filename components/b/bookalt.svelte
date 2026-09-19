<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c09546l0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="c09546l0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bookalt" {...props}></Icon>
