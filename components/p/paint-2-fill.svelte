<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lynimwjnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lynimwjnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:paint-2-fill" {...props}></Icon>
