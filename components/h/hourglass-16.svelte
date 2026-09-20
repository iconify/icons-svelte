<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up77eln0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<path clip-rule="evenodd" class="up77eln0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:hourglass-16" {...props}></Icon>
