<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqbv1hb3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vqbv1hb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:full-screen-square-outline" {...props}></Icon>
