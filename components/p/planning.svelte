<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzq2mebve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vzq2mebve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:planning" {...props}></Icon>
