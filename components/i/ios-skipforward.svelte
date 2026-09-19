<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5e6md03g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e5e6md03g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-skipforward" {...props}></Icon>
