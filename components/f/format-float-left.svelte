<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz33hqbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="yz33hqbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:format-float-left" {...props}></Icon>
