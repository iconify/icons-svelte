<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv15nl59b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="gv15nl59b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:dribble" {...props}></Icon>
