<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwny0ub1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gwny0ub1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hand-lizard" {...props}></Icon>
