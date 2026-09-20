<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdttmdz4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fdttmdz4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:person-booth-solid" {...props}></Icon>
