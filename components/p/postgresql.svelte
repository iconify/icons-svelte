<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybp5ncb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ybp5ncb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:postgresql" {...props}></Icon>
