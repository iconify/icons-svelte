<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st9q2dp3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="st9q2dp3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bath" {...props}></Icon>
