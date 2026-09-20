<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3fgfjbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3fgfjbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-2-code" {...props}></Icon>
