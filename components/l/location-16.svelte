<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfh5m5bzm.css';
import '../../css/k/kwvibbeog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bfh5m5bzm"/><path clip-rule="evenodd" class="kwvibbeog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:location-16" {...props}></Icon>
