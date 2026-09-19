<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zywzn6k9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zywzn6k9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:file-otf-small-filled" {...props}></Icon>
