<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in1b-kb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="in1b-kb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:numbers-2" {...props}></Icon>
