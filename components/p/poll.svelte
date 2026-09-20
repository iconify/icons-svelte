<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0igopbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c0igopbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:poll" {...props}></Icon>
