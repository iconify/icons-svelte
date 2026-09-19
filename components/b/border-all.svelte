<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esuh9ulmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esuh9ulmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:border-all" {...props}></Icon>
