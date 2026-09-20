<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfhqb8bno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfhqb8bno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:crane-off" {...props}></Icon>
