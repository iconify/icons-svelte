<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu7kue2rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lu7kue2rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-up-to-up-bracket" {...props}></Icon>
