<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drarmh_dl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drarmh_dl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:key-round" {...props}></Icon>
