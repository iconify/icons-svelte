<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk5kzdb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="jk5kzdb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:6" {...props}></Icon>
