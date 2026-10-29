<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ercj48bpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ercj48bpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:navigation-2" {...props}></Icon>
