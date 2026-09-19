<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frf7sf2bz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="frf7sf2bz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:quoteup" {...props}></Icon>
