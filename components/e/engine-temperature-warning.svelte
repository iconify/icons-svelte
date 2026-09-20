<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzuzk3k6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzuzk3k6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:engine-temperature-warning" {...props}></Icon>
