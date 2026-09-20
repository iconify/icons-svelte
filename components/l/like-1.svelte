<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt64sdmmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dt64sdmmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:like-1" {...props}></Icon>
