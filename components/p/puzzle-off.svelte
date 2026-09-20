<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkdegh_vw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkdegh_vw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:puzzle-off" {...props}></Icon>
