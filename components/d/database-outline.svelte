<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du4w56b8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="du4w56b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:database-outline" {...props}></Icon>
