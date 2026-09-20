<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fouad-q2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fouad-q2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:h-4" {...props}></Icon>
