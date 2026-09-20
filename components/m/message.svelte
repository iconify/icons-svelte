<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fui64t4ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fui64t4ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:message" {...props}></Icon>
