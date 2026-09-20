<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4c2zry7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4c2zry7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:notebook-minus" {...props}></Icon>
