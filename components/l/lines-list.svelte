<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlh2t63ch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wlh2t63ch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:lines-list" {...props}></Icon>
