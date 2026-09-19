<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cze689t2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cze689t2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:at" {...props}></Icon>
