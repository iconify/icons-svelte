<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4_i2lb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="v4_i2lb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:feedback" {...props}></Icon>
