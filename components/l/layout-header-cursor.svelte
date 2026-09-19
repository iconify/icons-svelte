<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmdhbbbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wmdhbbbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:layout-header-cursor" {...props}></Icon>
