<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjihciu7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bjihciu7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:justify-right-16" {...props}></Icon>
