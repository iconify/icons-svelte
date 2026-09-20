<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivve4qblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivve4qblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:battery-4-filled" {...props}></Icon>
