<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tipmx-bid.css';
import '../../css/g/gnxrllo6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tipmx-bid"/><path class="gnxrllo6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:file-search" {...props}></Icon>
