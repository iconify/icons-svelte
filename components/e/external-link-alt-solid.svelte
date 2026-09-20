<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_-acu8zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a_-acu8zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:external-link-alt-solid" {...props}></Icon>
