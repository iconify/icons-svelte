<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb90-ob5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kb90-ob5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:hand" {...props}></Icon>
