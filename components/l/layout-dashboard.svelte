<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdq5h-b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdq5h-b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-dashboard" {...props}></Icon>
