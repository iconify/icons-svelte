<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3j5e8bel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3j5e8bel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:cloud-moon-rain" {...props}></Icon>
