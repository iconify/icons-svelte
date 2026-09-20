<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjk479y-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="bjk479y-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:backup" {...props}></Icon>
