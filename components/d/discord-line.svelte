<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a66rwoh6p.css';
import '../../css/g/g3yeizbsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a66rwoh6p"/><path class="g3yeizbsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:discord-line" {...props}></Icon>
