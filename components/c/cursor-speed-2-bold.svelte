<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm0no-v2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gm0no-v2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cursor-speed-2-bold" {...props}></Icon>
