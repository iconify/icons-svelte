<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enqf0ab1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enqf0ab1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:refresh-solid" {...props}></Icon>
