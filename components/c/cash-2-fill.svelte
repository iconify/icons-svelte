<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy7yykbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jy7yykbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cash-2-fill" {...props}></Icon>
