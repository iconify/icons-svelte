<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u73kj-bgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u73kj-bgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-curve-down-right-16-solid" {...props}></Icon>
