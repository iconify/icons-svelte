<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhji1fb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qhji1fb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:dochub" {...props}></Icon>
