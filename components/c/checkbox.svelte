<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb9vtb3ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sb9vtb3ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:checkbox" {...props}></Icon>
