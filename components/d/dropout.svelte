<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_48-qoku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_48-qoku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dropout" {...props}></Icon>
