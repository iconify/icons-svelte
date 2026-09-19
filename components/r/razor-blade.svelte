<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bosx53r-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bosx53r-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:razor-blade" {...props}></Icon>
