<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alk-0vllj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="alk-0vllj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:at-solid" {...props}></Icon>
