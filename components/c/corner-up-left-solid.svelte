<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cquyq257a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cquyq257a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:corner-up-left-solid" {...props}></Icon>
