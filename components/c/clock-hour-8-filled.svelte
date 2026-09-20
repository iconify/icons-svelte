<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km1o2r7do.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km1o2r7do"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clock-hour-8-filled" {...props}></Icon>
