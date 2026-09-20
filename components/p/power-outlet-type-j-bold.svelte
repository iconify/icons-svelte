<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3as_xbml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y3as_xbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:power-outlet-type-j-bold" {...props}></Icon>
