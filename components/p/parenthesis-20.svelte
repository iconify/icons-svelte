<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxm7d5bdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hxm7d5bdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:parenthesis-20" {...props}></Icon>
