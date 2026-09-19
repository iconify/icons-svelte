<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmtfpgbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":721,"height":776};
const content = `<path class="bmtfpgbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:c-upper-case" {...props}></Icon>
