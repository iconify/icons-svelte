<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkvsifb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zkvsifb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:image-copy-filled" {...props}></Icon>
