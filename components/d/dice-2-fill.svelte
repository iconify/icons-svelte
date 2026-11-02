<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya_2pob1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ya_2pob1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dice-2-fill" {...props}></Icon>
