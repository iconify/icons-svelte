<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxfw4rbws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxfw4rbws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:align-box-bottom-center" {...props}></Icon>
