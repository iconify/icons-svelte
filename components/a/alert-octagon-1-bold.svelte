<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1pe50bpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z1pe50bpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:alert-octagon-1-bold" {...props}></Icon>
