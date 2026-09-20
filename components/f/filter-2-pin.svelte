<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/but20cbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="but20cbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-2-pin" {...props}></Icon>
