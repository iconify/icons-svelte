<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st24108fl.css';
import '../../css/g/gn6fo9ori.css';
import '../../css/p/pqifm1b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="st24108fl"/><path class="gn6fo9ori"/><path class="pqifm1b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:posts-carousel-horizontal-bold" {...props}></Icon>
