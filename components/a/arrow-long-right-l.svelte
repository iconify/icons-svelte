<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f23xl6srl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f23xl6srl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrow-long-right-l" {...props}></Icon>
