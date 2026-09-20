<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2jbinb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="u2jbinb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:no-entry-fill-12" {...props}></Icon>
