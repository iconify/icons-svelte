<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2q7bxbgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2q7bxbgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:arrows-shrink-h" {...props}></Icon>
