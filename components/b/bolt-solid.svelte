<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn-tu7bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jn-tu7bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:bolt-solid" {...props}></Icon>
