<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-cnqeb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":220,"height":220};
const content = `<path class="b-cnqeb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:milanote-dark" {...props}></Icon>
