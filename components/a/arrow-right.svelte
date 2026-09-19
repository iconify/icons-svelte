<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulyr7qb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ulyr7qb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:arrow-right" {...props}></Icon>
