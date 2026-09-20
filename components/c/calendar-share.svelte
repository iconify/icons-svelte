<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk3x2jjys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk3x2jjys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:calendar-share" {...props}></Icon>
