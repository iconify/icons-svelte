<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndwu0pb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ndwu0pb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:bell-fill" {...props}></Icon>
