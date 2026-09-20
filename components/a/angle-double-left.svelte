<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kerw-sino.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kerw-sino"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:angle-double-left" {...props}></Icon>
