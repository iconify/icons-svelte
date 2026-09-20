<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4buu26ch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y4buu26ch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:nav-threat-intel" {...props}></Icon>
