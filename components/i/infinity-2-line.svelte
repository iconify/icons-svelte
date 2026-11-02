<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dum__cb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dum__cb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:infinity-2-line" {...props}></Icon>
