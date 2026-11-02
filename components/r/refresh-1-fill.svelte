<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-n94acdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-n94acdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:refresh-1-fill" {...props}></Icon>
