<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t94ab6baa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t94ab6baa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:biceps-flexed-filled" {...props}></Icon>
