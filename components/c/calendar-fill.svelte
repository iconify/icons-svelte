<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljv734g0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljv734g0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-fill" {...props}></Icon>
