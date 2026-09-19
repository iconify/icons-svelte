<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-uk0zbnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g-uk0zbnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-ruled" {...props}></Icon>
