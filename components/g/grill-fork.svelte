<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w83lar4wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w83lar4wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:grill-fork" {...props}></Icon>
