<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1z178bmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y1z178bmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:comment" {...props}></Icon>
