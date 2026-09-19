<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfqbr2bgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mfqbr2bgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-dashed" {...props}></Icon>
