<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8r91twaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y8r91twaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:review-warning" {...props}></Icon>
