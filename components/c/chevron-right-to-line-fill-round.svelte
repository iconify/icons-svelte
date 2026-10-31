<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/litsavbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="litsavbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-right-to-line-fill-round" {...props}></Icon>
