<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwx5-1byy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cwx5-1byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hand-point-up" {...props}></Icon>
