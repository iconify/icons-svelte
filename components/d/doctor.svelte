<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwj8e1b9z.css';
import '../../css/i/i6isr1r7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bwj8e1b9z"/><path class="i6isr1r7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:doctor" {...props}></Icon>
