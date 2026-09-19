<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggkic8rwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ggkic8rwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:apple-small" {...props}></Icon>
