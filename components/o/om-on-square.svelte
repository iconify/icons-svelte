<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrxog6t6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hrxog6t6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:om-on-square" {...props}></Icon>
