<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq5zwab2c.css';
import '../../css/d/d1uus8zrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oq5zwab2c"/><path class="d1uus8zrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bird-alt" {...props}></Icon>
