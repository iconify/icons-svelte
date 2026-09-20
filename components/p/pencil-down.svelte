<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifsgc3bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifsgc3bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pencil-down" {...props}></Icon>
