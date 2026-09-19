<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq2n3-29f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eq2n3-29f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:load-balancer-application" {...props}></Icon>
