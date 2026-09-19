<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo4_cfbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vo4_cfbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:down-arrow" {...props}></Icon>
