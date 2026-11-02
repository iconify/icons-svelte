<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v32jgbb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v32jgbb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:contacts-2-line" {...props}></Icon>
