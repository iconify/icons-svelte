<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfkn82bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-3};
const content = `<path class="bfkn82bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:alarm-clock-f" {...props}></Icon>
