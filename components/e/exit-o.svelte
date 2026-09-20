<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4yb8v8ih.css';
import '../../css/u/u-uywrbac.css';
import '../../css/g/gzifgrbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s4yb8v8ih"/><path class="u-uywrbac"/><path class="gzifgrbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:exit-o" {...props}></Icon>
