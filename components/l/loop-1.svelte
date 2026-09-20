<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plkj6024y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plkj6024y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:loop-1" {...props}></Icon>
