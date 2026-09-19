<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfp51pbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":897,"height":1025};
const content = `<path class="hfp51pbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:evernote" {...props}></Icon>
