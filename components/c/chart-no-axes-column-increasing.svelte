<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjal8vb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjal8vb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chart-no-axes-column-increasing" {...props}></Icon>
