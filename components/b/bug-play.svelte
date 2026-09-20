<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml0269bhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ml0269bhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bug-play" {...props}></Icon>
