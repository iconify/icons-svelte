<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4zpm0b8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y4zpm0b8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:comment-dots" {...props}></Icon>
