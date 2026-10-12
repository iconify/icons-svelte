<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhh8rpb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nhh8rpb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cup-soda-filled" {...props}></Icon>
