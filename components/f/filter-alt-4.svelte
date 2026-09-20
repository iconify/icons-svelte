<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlmu-owkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="jlmu-owkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:filter-alt-4" {...props}></Icon>
