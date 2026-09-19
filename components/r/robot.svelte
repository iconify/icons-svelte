<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab2q78-0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ab2q78-0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:robot" {...props}></Icon>
