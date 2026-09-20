<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdk-94blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdk-94blo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-pinterest-filled" {...props}></Icon>
