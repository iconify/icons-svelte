<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/maou6okdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="maou6okdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:phone-question" {...props}></Icon>
