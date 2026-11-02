<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz7o56kpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pz7o56kpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pumpkin-fill" {...props}></Icon>
