<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2y2-bbea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2y2-bbea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:road-variant" {...props}></Icon>
