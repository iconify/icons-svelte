<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb55csbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yb55csbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:adjust-vertical-outline" {...props}></Icon>
