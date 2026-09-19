<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjp4mac5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":9,"height":16};
const content = `<path class="pjp4mac5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:caretleft" {...props}></Icon>
