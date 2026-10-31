<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuxwuxbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nuxwuxbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-dashed-gloss" {...props}></Icon>
