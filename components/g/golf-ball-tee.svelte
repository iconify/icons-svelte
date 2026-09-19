<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me2-5kvrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="me2-5kvrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:golf-ball-tee" {...props}></Icon>
