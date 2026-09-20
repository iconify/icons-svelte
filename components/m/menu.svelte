<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h514dvrgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h514dvrgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:menu" {...props}></Icon>
