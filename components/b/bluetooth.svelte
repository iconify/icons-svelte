<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz7llccqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gz7llccqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:bluetooth" {...props}></Icon>
