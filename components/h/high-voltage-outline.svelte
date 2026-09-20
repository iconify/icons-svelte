<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvlp93b-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvlp93b-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:high-voltage-outline" {...props}></Icon>
