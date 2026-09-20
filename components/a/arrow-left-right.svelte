<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et0g50bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="et0g50bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-left-right" {...props}></Icon>
