<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrbszhkyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vrbszhkyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gift2" {...props}></Icon>
