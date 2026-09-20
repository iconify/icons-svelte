<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zror_sbrn.css';
import '../../css/c/c_5bp2b7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zror_sbrn"/><path class="c_5bp2b7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:person-cursor-16" {...props}></Icon>
