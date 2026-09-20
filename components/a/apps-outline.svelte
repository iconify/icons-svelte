<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr368eb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tr368eb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:apps-outline" {...props}></Icon>
