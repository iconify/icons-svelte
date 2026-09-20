<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v31zzfo0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":16};
const content = `<path class="v31zzfo0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:chevron-right" {...props}></Icon>
