<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0jvsm82e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q0jvsm82e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:in-ear-headphones-solid" {...props}></Icon>
