<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trifqr1dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trifqr1dn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-down-left-from-circle" {...props}></Icon>
