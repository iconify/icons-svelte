<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdej6-b0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdej6-b0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:file-plus-filled" {...props}></Icon>
