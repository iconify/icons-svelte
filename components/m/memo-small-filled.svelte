<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akb6c-68i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="akb6c-68i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:memo-small-filled" {...props}></Icon>
