<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzql8ab7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzql8ab7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-2-filled" {...props}></Icon>
