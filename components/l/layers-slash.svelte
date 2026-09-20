<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyvagkvjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fyvagkvjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:layers-slash" {...props}></Icon>
