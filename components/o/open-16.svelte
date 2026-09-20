<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3z9cbmwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a3z9cbmwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:open-16" {...props}></Icon>
