<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyowgpbei.css';
import '../../css/n/nwz75bygh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyowgpbei"/><path class="nwz75bygh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-building-house" {...props}></Icon>
