<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m33jx7brg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m33jx7brg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:bookstack" {...props}></Icon>
