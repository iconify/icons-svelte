<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymfmxbbhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymfmxbbhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chip-fill" {...props}></Icon>
