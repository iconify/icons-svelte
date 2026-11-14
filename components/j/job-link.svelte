<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-_n6bcga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-_n6bcga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:job-link" {...props}></Icon>
