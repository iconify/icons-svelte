<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anc5s55-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="anc5s55-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:document-add" {...props}></Icon>
