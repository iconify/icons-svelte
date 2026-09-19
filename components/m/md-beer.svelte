<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_ci_razz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w_ci_razz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-beer" {...props}></Icon>
