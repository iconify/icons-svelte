<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uahd8vp5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uahd8vp5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:lock-open" {...props}></Icon>
