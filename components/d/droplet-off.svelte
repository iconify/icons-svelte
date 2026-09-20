<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqb7r5b8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqb7r5b8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:droplet-off" {...props}></Icon>
