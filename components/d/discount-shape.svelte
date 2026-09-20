<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a69vztzpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a69vztzpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:discount-shape" {...props}></Icon>
