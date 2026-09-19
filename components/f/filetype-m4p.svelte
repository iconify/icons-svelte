<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9-czvb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q9-czvb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-m4p" {...props}></Icon>
