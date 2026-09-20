<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt2b5di-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="pt2b5di-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:add-circle-small-filled" {...props}></Icon>
