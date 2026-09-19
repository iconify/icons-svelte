<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwup8r63e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwup8r63e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:flag-filled" {...props}></Icon>
