<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq462eq0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="aq462eq0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:autoplay" {...props}></Icon>
