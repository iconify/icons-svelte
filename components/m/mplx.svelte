<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1zu-7ago.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1zu-7ago"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mplx" {...props}></Icon>
