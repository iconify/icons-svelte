<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2tai3nwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="v2tai3nwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:computer" {...props}></Icon>
