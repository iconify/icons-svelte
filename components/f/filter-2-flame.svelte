<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_gn8skvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_gn8skvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-2-flame" {...props}></Icon>
