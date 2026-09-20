<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zebs4qb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zebs4qb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:layers-1-16" {...props}></Icon>
