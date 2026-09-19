<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_pgce4lp.css';
import '../../css/p/pn-6xpb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_pgce4lp"/><path class="pn-6xpb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-down-left-stroke-square-filled" {...props}></Icon>
