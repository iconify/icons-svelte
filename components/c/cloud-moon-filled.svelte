<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufep9qyxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufep9qyxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-moon-filled" {...props}></Icon>
