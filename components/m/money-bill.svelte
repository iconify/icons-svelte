<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4mym1_0y.css';
import '../../css/l/ln6rcys8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4mym1_0y"/><path class="ln6rcys8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:money-bill" {...props}></Icon>
