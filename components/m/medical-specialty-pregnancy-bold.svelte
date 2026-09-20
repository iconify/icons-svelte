<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_9pn8b4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_9pn8b4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:medical-specialty-pregnancy-bold" {...props}></Icon>
