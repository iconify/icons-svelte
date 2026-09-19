<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mae22ab3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mae22ab3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:expand" {...props}></Icon>
