<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p24z8pbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p24z8pbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:bed-filled" {...props}></Icon>
