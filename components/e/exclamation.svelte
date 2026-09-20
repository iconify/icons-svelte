<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf2yhjbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cf2yhjbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:exclamation" {...props}></Icon>
