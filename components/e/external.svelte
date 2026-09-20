<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm_kizbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="pm_kizbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:external" {...props}></Icon>
