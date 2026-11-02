<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1_7nbc-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1_7nbc-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hand-platter-fill" {...props}></Icon>
