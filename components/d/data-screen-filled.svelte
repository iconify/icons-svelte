<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8qxwmb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d8qxwmb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:data-screen-filled" {...props}></Icon>
