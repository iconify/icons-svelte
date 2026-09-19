<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdag-oi8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdag-oi8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:pull" {...props}></Icon>
