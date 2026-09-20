<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir3tr1blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ir3tr1blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:icon" {...props}></Icon>
