<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h23i9q6my.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1760};
const content = `<path class="h23i9q6my"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:male" {...props}></Icon>
