<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9aiypbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9aiypbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:grid-circle" {...props}></Icon>
