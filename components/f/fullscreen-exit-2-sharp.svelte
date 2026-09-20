<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1d79ebop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1d79ebop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:fullscreen-exit-2-sharp" {...props}></Icon>
