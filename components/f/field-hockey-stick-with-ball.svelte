<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azkzdtbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="azkzdtbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:field-hockey-stick-with-ball" {...props}></Icon>
