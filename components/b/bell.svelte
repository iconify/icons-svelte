<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot2szjwel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ot2szjwel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:bell" {...props}></Icon>
