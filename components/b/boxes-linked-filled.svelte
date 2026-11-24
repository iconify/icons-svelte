<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5q_y96bd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k5q_y96bd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:boxes-linked-filled" {...props}></Icon>
