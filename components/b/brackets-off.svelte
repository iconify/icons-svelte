<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2n3tebyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2n3tebyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brackets-off" {...props}></Icon>
