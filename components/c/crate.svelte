<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxz9n17ru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rxz9n17ru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:crate" {...props}></Icon>
