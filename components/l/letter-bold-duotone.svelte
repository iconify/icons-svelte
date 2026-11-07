<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxyrlcb9h.css';
import '../../css/a/avjg2qbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxyrlcb9h"/><path class="avjg2qbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:letter-bold-duotone" {...props}></Icon>
