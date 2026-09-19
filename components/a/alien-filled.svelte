<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxefai00q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxefai00q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:alien-filled" {...props}></Icon>
