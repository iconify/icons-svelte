<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q20ot-b8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q20ot-b8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:arrow-right-outline" {...props}></Icon>
