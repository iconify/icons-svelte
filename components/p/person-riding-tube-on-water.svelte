<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3k4apb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u3k4apb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-riding-tube-on-water" {...props}></Icon>
