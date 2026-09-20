<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj2nozalb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rj2nozalb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pointer-x" {...props}></Icon>
