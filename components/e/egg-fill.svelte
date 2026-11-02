<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bldn_f5bn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bldn_f5bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:egg-fill" {...props}></Icon>
