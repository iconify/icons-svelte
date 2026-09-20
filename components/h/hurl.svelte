<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrtxn5dxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lrtxn5dxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:hurl" {...props}></Icon>
