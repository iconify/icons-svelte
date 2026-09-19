<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m621oab_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="m621oab_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:left-hook-arrow-small" {...props}></Icon>
