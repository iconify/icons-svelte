<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irlsicc8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="irlsicc8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:allocine" {...props}></Icon>
