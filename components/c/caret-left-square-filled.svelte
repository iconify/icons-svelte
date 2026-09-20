<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0w6r0vef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m0w6r0vef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:caret-left-square-filled" {...props}></Icon>
