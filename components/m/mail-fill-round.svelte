<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1tjmtith.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1tjmtith"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mail-fill-round" {...props}></Icon>
