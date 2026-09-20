<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgd33ebwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgd33ebwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:e" {...props}></Icon>
