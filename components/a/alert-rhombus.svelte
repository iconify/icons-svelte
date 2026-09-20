<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2yu1ib7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="h2yu1ib7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alert-rhombus" {...props}></Icon>
