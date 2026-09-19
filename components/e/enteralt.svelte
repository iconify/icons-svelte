<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou-xpxb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ou-xpxb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:enteralt" {...props}></Icon>
