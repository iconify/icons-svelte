<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grm9sdwah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grm9sdwah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clock-hour-11" {...props}></Icon>
