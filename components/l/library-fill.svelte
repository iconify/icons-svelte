<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe3uj_7em.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pe3uj_7em"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:library-fill" {...props}></Icon>
