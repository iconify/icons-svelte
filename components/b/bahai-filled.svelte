<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm3ghdgpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gm3ghdgpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bahai-filled" {...props}></Icon>
