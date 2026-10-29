<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxkark7nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxkark7nm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:columns-solid" {...props}></Icon>
