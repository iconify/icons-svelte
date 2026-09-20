<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_reddbpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_reddbpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:coins" {...props}></Icon>
