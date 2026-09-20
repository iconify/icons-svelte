<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haijt0bwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="haijt0bwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:align-text-justify-outline" {...props}></Icon>
