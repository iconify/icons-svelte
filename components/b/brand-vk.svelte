<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbo42nb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbo42nb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-vk" {...props}></Icon>
