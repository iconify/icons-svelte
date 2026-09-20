<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk3yj5b7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk3yj5b7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clock-hour-4" {...props}></Icon>
