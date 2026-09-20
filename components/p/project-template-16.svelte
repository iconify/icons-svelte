<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teorf6boz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="teorf6boz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:project-template-16" {...props}></Icon>
