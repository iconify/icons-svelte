<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynnt_ijek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynnt_ijek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:refresh" {...props}></Icon>
