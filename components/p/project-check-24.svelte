<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt6oj8b5t.css';
import '../../css/z/zdpv8zbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wt6oj8b5t"/><path class="zdpv8zbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:project-check-24" {...props}></Icon>
