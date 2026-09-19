<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uml44qbtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uml44qbtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:queue-01" {...props}></Icon>
