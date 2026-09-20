<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzk00ybyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzk00ybyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:exclamation-circle-solid" {...props}></Icon>
