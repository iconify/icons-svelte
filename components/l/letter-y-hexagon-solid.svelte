<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es4gnh0fa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="es4gnh0fa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-y-hexagon-solid" {...props}></Icon>
