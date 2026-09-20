<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hem1vcbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hem1vcbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:edit-bulk" {...props}></Icon>
