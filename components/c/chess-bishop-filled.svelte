<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc-_tnb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wc-_tnb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chess-bishop-filled" {...props}></Icon>
