<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw_389blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mw_389blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:audiobookrequest-dark" {...props}></Icon>
