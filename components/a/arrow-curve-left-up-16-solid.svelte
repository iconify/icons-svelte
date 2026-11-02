<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yiomhwxsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yiomhwxsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-curve-left-up-16-solid" {...props}></Icon>
