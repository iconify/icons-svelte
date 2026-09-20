<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzo6s_4tz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzo6s_4tz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dual-sim-1-line" {...props}></Icon>
