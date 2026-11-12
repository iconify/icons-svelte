<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgtbb6h2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgtbb6h2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bookmark-exclamation" {...props}></Icon>
