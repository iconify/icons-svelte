<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2k6cl0mo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2k6cl0mo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-minus" {...props}></Icon>
