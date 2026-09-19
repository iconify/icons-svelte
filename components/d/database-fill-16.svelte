<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huj05qb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="huj05qb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:database-fill-16" {...props}></Icon>
