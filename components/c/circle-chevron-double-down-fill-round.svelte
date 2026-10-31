<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaw68pbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eaw68pbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-chevron-double-down-fill-round" {...props}></Icon>
