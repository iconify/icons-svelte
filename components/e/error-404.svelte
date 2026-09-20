<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xktlhq9bl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xktlhq9bl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:error-404" {...props}></Icon>
