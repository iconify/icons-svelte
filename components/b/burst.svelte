<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owfwkcmnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="owfwkcmnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:burst" {...props}></Icon>
