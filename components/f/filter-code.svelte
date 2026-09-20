<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksffx8bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksffx8bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-code" {...props}></Icon>
