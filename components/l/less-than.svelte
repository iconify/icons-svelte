<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i48xvju3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="i48xvju3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:less-than" {...props}></Icon>
