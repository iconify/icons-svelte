<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4406ob8i.css';
import '../../css/y/yg04rqb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i4406ob8i"/><path class="yg04rqb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:right-down" {...props}></Icon>
