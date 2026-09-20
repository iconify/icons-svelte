<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7d75gb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e7d75gb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:doc-versions" {...props}></Icon>
