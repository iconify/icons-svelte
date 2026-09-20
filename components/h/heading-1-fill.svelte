<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-zcbiwap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-zcbiwap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heading-1-fill" {...props}></Icon>
