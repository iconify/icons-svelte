<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2ol84b2g.css';
import '../../css/i/iwbhjtb_d.css';
import '../../css/f/f4fekj7yf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2ol84b2g"/><path class="iwbhjtb_d"/><path class="f4fekj7yf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:land" {...props}></Icon>
