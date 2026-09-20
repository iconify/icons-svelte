<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwvttg8ed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwvttg8ed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:eyeglass-filled" {...props}></Icon>
