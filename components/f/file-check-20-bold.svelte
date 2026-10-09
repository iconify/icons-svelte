<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8im5qk_h.css';
import '../../css/z/z13h4jbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w8im5qk_h"/><path class="z13h4jbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-check-20-bold" {...props}></Icon>
