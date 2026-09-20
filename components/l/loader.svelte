<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8fay54xn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8fay54xn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:loader" {...props}></Icon>
