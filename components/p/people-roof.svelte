<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igc3gkbwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="igc3gkbwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:people-roof" {...props}></Icon>
