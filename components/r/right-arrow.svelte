<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6y6ojb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v6y6ojb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:right-arrow" {...props}></Icon>
