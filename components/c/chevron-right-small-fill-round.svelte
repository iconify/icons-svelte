<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt0zfmnsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pt0zfmnsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-right-small-fill-round" {...props}></Icon>
