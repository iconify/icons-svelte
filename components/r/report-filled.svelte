<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh5bd7bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oh5bd7bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:report-filled" {...props}></Icon>
