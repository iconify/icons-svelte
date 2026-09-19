<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu9bbcbtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wu9bbcbtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:reader-comment" {...props}></Icon>
