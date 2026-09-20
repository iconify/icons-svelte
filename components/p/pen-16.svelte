<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec-8y-b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ec-8y-b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:pen-16" {...props}></Icon>
