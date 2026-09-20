<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grfzoublw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grfzoublw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:music3-filled" {...props}></Icon>
