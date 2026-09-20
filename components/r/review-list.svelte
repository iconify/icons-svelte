<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t32qhobhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t32qhobhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:review-list" {...props}></Icon>
