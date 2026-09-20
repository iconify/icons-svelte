<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elwig4b_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elwig4b_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:motorbike-filled" {...props}></Icon>
