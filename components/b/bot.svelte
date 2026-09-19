<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1tr5shfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o1tr5shfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:bot" {...props}></Icon>
