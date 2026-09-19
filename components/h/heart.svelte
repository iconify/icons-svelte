<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usxi8y_4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usxi8y_4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:heart" {...props}></Icon>
