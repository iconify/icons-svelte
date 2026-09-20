<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4g9cnbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n4g9cnbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:kind" {...props}></Icon>
