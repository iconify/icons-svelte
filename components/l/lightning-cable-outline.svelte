<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d49j50b_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d49j50b_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:lightning-cable-outline" {...props}></Icon>
