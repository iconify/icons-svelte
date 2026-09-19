<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfqyd7-2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfqyd7-2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:handbag" {...props}></Icon>
