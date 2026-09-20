<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd65e6q8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jd65e6q8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:brightness-2" {...props}></Icon>
