<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_15mh_uj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":610,"height":700};
const content = `<path class="x_15mh_uj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:ellipsis" {...props}></Icon>
