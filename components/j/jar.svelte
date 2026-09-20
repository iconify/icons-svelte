<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/howr7c5eb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="howr7c5eb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:jar" {...props}></Icon>
