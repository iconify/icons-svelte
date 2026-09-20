<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no9xs_bel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="no9xs_bel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:projector-fill" {...props}></Icon>
