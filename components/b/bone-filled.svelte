<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esm08ypvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esm08ypvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bone-filled" {...props}></Icon>
