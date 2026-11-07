<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubrgnsref.css';
import '../../css/x/xl-jarb6g.css';
import '../../css/p/p8b3qu2bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubrgnsref"/><path class="xl-jarb6g"/><path class="p8b3qu2bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bomb-bold" {...props}></Icon>
