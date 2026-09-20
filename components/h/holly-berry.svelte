<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2j59xf0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c2j59xf0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:holly-berry" {...props}></Icon>
