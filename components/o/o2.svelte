<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsvjai1rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsvjai1rm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:o2" {...props}></Icon>
