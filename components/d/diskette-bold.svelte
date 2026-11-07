<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmt358bze.css';
import '../../css/d/dre6y_9-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hmt358bze"/><path class="dre6y_9-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:diskette-bold" {...props}></Icon>
