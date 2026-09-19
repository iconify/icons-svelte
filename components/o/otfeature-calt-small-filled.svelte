<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1p9zxbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="d1p9zxbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-calt-small-filled" {...props}></Icon>
