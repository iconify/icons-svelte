<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndycdl2mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ndycdl2mp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:back-arrow" {...props}></Icon>
