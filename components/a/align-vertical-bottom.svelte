<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic5m1gpux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ic5m1gpux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:align-vertical-bottom" {...props}></Icon>
