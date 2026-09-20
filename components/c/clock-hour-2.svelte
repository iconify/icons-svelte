<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwnejlrdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwnejlrdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clock-hour-2" {...props}></Icon>
