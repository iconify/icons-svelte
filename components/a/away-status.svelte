<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya4dmxbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ya4dmxbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:away-status" {...props}></Icon>
