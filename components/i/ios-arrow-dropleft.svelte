<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkskkgb5x.css';
import '../../css/n/nek1lu3pi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nkskkgb5x"/><path class="nek1lu3pi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-arrow-dropleft" {...props}></Icon>
