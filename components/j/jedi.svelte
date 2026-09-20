<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skyrij1cm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="skyrij1cm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:jedi" {...props}></Icon>
