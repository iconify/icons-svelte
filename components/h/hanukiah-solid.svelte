<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbjv7lb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fbjv7lb0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hanukiah-solid" {...props}></Icon>
