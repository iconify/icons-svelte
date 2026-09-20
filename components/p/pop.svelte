<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw--h24ia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lw--h24ia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pop" {...props}></Icon>
