<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clawo4fnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="clawo4fnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:geo-active" {...props}></Icon>
