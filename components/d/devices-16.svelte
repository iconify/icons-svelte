<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7degyn_m.css';
import '../../css/w/wt6yq6kuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v7degyn_m"/><path class="wt6yq6kuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:devices-16" {...props}></Icon>
