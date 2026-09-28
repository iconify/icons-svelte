<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1nmlabip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="f1nmlabip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:heading-level-2" {...props}></Icon>
