<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w62k3153g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w62k3153g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:border-none" {...props}></Icon>
