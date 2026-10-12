<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuuehgbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xuuehgbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cake-slice-filled" {...props}></Icon>
