<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_57x5kqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_57x5kqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clock-hour-12-filled" {...props}></Icon>
