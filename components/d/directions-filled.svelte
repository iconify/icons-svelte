<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aezcewbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aezcewbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:directions-filled" {...props}></Icon>
