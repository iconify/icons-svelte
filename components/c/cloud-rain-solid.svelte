<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-j50jyre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-j50jyre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:cloud-rain-solid" {...props}></Icon>
