<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7b5412_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7b5412_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:gitlab" {...props}></Icon>
