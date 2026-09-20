<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prjf5xbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":16};
const content = `<path class="prjf5xbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:dash" {...props}></Icon>
