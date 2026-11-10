<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uum3rn3oq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uum3rn3oq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:braces" {...props}></Icon>
