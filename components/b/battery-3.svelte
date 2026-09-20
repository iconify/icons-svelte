<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef3dopb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ef3dopb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:battery-3" {...props}></Icon>
