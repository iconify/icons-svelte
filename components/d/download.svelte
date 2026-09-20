<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8at4kbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i8at4kbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:download" {...props}></Icon>
