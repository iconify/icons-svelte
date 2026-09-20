<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7nt30brc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7nt30brc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-fact-alt-1-line" {...props}></Icon>
