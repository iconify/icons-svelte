<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1yrw_kmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="v1yrw_kmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-sups-small-filled" {...props}></Icon>
