<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxbsks6my.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxbsks6my"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-opera-filled" {...props}></Icon>
