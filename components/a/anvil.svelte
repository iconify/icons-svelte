<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_5201bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="s_5201bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:anvil" {...props}></Icon>
