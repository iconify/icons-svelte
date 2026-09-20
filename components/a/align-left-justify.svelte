<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avrldqbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avrldqbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:align-left-justify" {...props}></Icon>
