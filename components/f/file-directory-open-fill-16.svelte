<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhpwkq3jg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uhpwkq3jg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-directory-open-fill-16" {...props}></Icon>
