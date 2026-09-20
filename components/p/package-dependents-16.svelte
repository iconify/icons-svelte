<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjfwagpfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yjfwagpfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:package-dependents-16" {...props}></Icon>
