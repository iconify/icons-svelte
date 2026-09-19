<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bodiu-ptb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="bodiu-ptb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:location-slash" {...props}></Icon>
