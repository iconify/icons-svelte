<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gplnk4bil.css';
import '../../css/k/k_txi0raq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gplnk4bil"/><path class="k_txi0raq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:orbit-filled" {...props}></Icon>
