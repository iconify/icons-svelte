<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlvzh0b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xlvzh0b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:horizontal-rule-fill-16" {...props}></Icon>
