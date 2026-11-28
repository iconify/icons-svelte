<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcm9zqbhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcm9zqbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:calendar-heart" {...props}></Icon>
