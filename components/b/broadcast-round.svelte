<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy61r9uhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sy61r9uhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:broadcast-round" {...props}></Icon>
