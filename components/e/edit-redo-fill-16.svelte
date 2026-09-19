<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9ym0t80c.css';
import '../../css/a/ae-rsdbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v9ym0t80c"/><path class="ae-rsdbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:edit-redo-fill-16" {...props}></Icon>
