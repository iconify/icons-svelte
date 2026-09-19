<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/capp2ob6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="capp2ob6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:children" {...props}></Icon>
