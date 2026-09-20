<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc21hcbgh.css';
import '../../css/g/gis2ovb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hc21hcbgh"/><path clip-rule="evenodd" class="gis2ovb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:browser" {...props}></Icon>
