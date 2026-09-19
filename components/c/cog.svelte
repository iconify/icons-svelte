<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6jhhfj4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c6jhhfj4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:cog" {...props}></Icon>
