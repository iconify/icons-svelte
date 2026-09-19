<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8kqwv81x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c8kqwv81x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:rectangle-small" {...props}></Icon>
