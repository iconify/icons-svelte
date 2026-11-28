<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhkirac3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhkirac3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:health-cross-solid" {...props}></Icon>
