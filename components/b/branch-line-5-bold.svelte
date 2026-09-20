<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrne95bef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nrne95bef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:branch-line-5-bold" {...props}></Icon>
