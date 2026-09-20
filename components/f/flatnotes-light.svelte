<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtxcrobpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jtxcrobpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flatnotes-light" {...props}></Icon>
