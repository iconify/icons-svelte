<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcw8lh66i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xcw8lh66i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:envelope-open" {...props}></Icon>
