<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7wes_f8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j7wes_f8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:plug-solid" {...props}></Icon>
