<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhqehtb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhqehtb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:horse" {...props}></Icon>
