<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5unvac5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="f5unvac5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:dependency-add" {...props}></Icon>
