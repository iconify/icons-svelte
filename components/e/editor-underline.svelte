<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_2v6m4fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r_2v6m4fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:editor-underline" {...props}></Icon>
