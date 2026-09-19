<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnet0zdkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnet0zdkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:menorah-filled" {...props}></Icon>
