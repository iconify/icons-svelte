<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbdtxqbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbdtxqbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-zwift" {...props}></Icon>
