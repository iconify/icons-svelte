<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arv7yvchw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="arv7yvchw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:fulcrum" {...props}></Icon>
