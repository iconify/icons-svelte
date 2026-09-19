<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-fum9tds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o-fum9tds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:collection-fill" {...props}></Icon>
