<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi-q769oq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi-q769oq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-audible" {...props}></Icon>
