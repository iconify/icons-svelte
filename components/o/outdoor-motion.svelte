<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twyyp55es.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twyyp55es"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:outdoor-motion" {...props}></Icon>
