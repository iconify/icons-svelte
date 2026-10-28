<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4s6s33fq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4s6s33fq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:octagon" {...props}></Icon>
