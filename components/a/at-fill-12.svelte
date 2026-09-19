<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v27c71pnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="v27c71pnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:at-fill-12" {...props}></Icon>
