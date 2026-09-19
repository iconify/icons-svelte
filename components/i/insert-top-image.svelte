<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krdf7zkuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krdf7zkuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:insert-top-image" {...props}></Icon>
