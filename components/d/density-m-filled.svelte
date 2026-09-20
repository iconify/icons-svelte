<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhwyy6cym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hhwyy6cym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:density-m-filled" {...props}></Icon>
