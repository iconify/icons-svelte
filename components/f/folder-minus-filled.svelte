<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lddwqxbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lddwqxbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:folder-minus-filled" {...props}></Icon>
