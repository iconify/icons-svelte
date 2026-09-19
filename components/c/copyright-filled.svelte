<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlur37j2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xlur37j2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:copyright-filled" {...props}></Icon>
