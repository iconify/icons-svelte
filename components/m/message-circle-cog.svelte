<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt7dxsrju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt7dxsrju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-circle-cog" {...props}></Icon>
