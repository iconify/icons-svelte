<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee6bkskmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ee6bkskmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pencil-lock-outline" {...props}></Icon>
