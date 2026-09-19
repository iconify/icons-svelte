<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxvbazz0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qxvbazz0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:play-stroke-12" {...props}></Icon>
