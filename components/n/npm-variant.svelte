<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftv_mlbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftv_mlbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:npm-variant" {...props}></Icon>
