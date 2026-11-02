<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lattsdb3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lattsdb3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:building-1-fill" {...props}></Icon>
