<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt9lw47qv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dt9lw47qv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:drag-outline" {...props}></Icon>
