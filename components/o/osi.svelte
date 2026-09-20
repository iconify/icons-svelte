<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o40ncj9os.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o40ncj9os"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:osi" {...props}></Icon>
