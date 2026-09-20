<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqtabzbbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqtabzbbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-34-small" {...props}></Icon>
