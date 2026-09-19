<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v129qbbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v129qbbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:male-and-female-outline-24px" {...props}></Icon>
