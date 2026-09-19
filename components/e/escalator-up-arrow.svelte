<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg6p6hbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mg6p6hbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:escalator-up-arrow" {...props}></Icon>
