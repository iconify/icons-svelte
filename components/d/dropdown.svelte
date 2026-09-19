<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uot15gzqk.css';
import '../../css/n/nf2tmmxki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uot15gzqk"/><path class="nf2tmmxki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dropdown" {...props}></Icon>
