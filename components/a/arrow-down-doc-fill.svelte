<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7-deq81w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="v7-deq81w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-down-doc-fill" {...props}></Icon>
