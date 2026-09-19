<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb8gddblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rb8gddblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:eye-closed" {...props}></Icon>
