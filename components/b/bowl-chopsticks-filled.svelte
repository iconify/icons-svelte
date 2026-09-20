<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxg_zqbpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxg_zqbpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bowl-chopsticks-filled" {...props}></Icon>
