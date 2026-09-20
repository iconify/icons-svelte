<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvkmykbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvkmykbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:circle-off" {...props}></Icon>
