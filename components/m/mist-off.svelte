<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8l6ylz_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8l6ylz_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mist-off" {...props}></Icon>
