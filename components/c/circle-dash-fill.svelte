<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dspnf0f_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dspnf0f_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-dash-fill" {...props}></Icon>
