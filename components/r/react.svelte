<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb97t2bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yb97t2bew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:react" {...props}></Icon>
