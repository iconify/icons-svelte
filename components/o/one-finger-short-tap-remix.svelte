<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7by1o2ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w7by1o2ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:one-finger-short-tap-remix" {...props}></Icon>
