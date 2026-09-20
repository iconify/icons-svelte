<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9e74ubno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9e74ubno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:apps-filled" {...props}></Icon>
