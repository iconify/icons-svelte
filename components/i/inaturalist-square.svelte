<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okt830xak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="okt830xak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:inaturalist-square" {...props}></Icon>
