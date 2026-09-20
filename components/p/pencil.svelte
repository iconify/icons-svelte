<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/giw_6scvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="giw_6scvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:pencil" {...props}></Icon>
