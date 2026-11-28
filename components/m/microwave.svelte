<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzwkyi3nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzwkyi3nd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:microwave" {...props}></Icon>
