<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iue2-2gxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iue2-2gxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:chip" {...props}></Icon>
