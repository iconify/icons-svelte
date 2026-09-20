<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctd19f6wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctd19f6wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrows-rotate-filled" {...props}></Icon>
