<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqbx91-km.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqbx91-km"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:box-align-right" {...props}></Icon>
