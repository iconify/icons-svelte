<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-gtejb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d-gtejb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:fuel" {...props}></Icon>
