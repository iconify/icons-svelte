<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr150ojmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sr150ojmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrows-left-right" {...props}></Icon>
