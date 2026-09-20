<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alf0tiuoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="alf0tiuoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:border-bottom" {...props}></Icon>
