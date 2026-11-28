<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lliwufbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lliwufbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clock-x" {...props}></Icon>
