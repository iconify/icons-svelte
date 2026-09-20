<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t72jh4bsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="t72jh4bsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:envelope-closed" {...props}></Icon>
