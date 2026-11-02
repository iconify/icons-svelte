<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyt_8j3vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyt_8j3vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:delete-3-fill" {...props}></Icon>
