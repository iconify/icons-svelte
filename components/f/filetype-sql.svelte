<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uygpo7yry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uygpo7yry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-sql" {...props}></Icon>
