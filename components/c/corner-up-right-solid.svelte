<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvi4jzfbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvi4jzfbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:corner-up-right-solid" {...props}></Icon>
