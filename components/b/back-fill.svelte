<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4_pnfccj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4_pnfccj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:back-fill" {...props}></Icon>
