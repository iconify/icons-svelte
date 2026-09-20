<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn0a5zknn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jn0a5zknn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:cheese" {...props}></Icon>
