<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llgj6_bel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llgj6_bel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-26-small" {...props}></Icon>
