<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9eje8s8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y9eje8s8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:check-double" {...props}></Icon>
