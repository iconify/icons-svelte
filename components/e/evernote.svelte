<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx3wucg6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="yx3wucg6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:evernote" {...props}></Icon>
